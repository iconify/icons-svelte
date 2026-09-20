<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gk72nlbta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gk72nlbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:lemon-2" {...props}></Icon>
