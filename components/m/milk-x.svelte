<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9n0dlbuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9n0dlbuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:milk-x" {...props}></Icon>
