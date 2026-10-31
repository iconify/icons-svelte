<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd96iokhh.css';
import '../../css/m/m6ybx_b2r.css';
import '../../css/b/bjmk_0bxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="wd96iokhh"/><path class="m6ybx_b2r"/><path class="bjmk_0bxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:madagascar" {...props}></Icon>
