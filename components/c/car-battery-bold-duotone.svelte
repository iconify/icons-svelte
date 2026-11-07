<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yallzciul.css';
import '../../css/m/m-7zrk-pf.css';
import '../../css/p/pnuw8wf1j.css';
import '../../css/f/f93hblbdf.css';
import '../../css/d/d7qschzxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yallzciul"/><path class="m-7zrk-pf"/><path class="pnuw8wf1j"/><path class="f93hblbdf"/><path class="d7qschzxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:car-battery-bold-duotone" {...props}></Icon>
