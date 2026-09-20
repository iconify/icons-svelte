<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f0nmc9b2i.css';
import '../../css/y/yrzxlfb2f.css';
import '../../css/e/er3cb1bwk.css';
import '../../css/a/a80uv-e5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f0nmc9b2i"/><path class="yrzxlfb2f"/><path class="er3cb1bwk"/><path class="a80uv-e5n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chimney-1" {...props}></Icon>
