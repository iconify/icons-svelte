<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yetj49bbr.css';
import '../../css/c/cad3x_r9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yetj49bbr"/><path class="cad3x_r9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file-badge-16" {...props}></Icon>
