<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_zi44brh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_zi44brh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:lumen" {...props}></Icon>
