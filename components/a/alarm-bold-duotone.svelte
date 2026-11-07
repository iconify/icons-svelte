<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_-_yx_oi.css';
import '../../css/g/gfnljuhlb.css';
import '../../css/k/kube8drda.css';
import '../../css/j/jf1pbcbud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_-_yx_oi"/><path class="gfnljuhlb"/><path class="kube8drda"/><path class="jf1pbcbud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:alarm-bold-duotone" {...props}></Icon>
