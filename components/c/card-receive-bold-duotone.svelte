<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kclej1bpd.css';
import '../../css/m/m-c56pbgj.css';
import '../../css/y/yb1t-pwor.css';
import '../../css/o/ogh4q1bay.css';
import '../../css/s/s6qd-zbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kclej1bpd"/><path class="m-c56pbgj"/><path class="yb1t-pwor"/><path class="ogh4q1bay"/><path class="s6qd-zbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:card-receive-bold-duotone" {...props}></Icon>
