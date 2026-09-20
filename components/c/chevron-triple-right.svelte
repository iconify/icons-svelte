<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/c/c1qs2i.css';
import '../../css/a/axqjwt.css';
import '../../css/z/zt_tcx.css';
import '../../css/s/so-from-12.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c c1qs2i"/><path class="a0m25c axqjwt"/><path class="a0m25c zt_tcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:chevron-triple-right" {...props}></Icon>
