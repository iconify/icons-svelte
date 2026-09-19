<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxz1d9zdu.css';
import '../../css/n/nf61udb6z.css';
import '../../css/t/t-y-wfbey.css';
import '../../css/a/aufd3gbbo.css';
import '../../css/s/sn56facnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gxz1d9zdu"/><path class="nf61udb6z"/><path class="t-y-wfbey"/><path class="aufd3gbbo"/><path class="sn56facnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:deployment" {...props}></Icon>
