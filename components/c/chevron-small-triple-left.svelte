<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/e/ew1mpj.css';
import '../../css/m/m0_dsb.css';
import '../../css/j/ju1zuh.css';
import '../../css/s/so-from-10.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c ew1mpj"/><path class="a0m25c m0_dsb"/><path class="a0m25c ju1zuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:chevron-small-triple-left" {...props}></Icon>
