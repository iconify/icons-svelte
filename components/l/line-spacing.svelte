<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e750u5bvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e750u5bvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:line-spacing" {...props}></Icon>
