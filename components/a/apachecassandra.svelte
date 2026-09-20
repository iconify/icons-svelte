<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu7-0-q3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bu7-0-q3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:apachecassandra" {...props}></Icon>
