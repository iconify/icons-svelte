<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/x/xl3inp.css';
import '../../css/p/pad0sq.css';
import '../../css/h/h8srsm.css';
import '../../css/s/so-from-12.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c xl3inp"/><path class="a0m25c pad0sq"/><path class="a0m25c h8srsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:chevron-triple-left" {...props}></Icon>
