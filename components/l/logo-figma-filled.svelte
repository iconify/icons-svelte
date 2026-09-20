<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6-kq4cwx.css';
import '../../css/d/d3bnnkbfx.css';
import '../../css/b/b3ef9_bsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u6-kq4cwx"/><path class="d3bnnkbfx"/><path class="b3ef9_bsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-figma-filled" {...props}></Icon>
