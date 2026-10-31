<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dki-1w-8i.css';
import '../../css/s/s1c8xvkzj.css';
import '../../css/i/iq_z596tt.css';
import '../../css/y/y1n_k57xm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="dki-1w-8i"/><path class="s1c8xvkzj"/><path class="iq_z596tt"/><path class="y1n_k57xm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:hong-kong" {...props}></Icon>
