<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7u9ox.css';
import '../../css/a/a0m25c.css';
import '../../css/o/ofn98h.css';
import '../../css/n/nrq0xo.css';
import '../../css/f/fill-to-0.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-from-64.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x7u9ox"/><path class="a0m25c ofn98h"/><path class="a0m25c nrq0xo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:email-opened-twotone" {...props}></Icon>
