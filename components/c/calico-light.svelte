<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kp79mfbbx.css';
import '../../css/w/wkurt-npl.css';
import '../../css/g/gk6duor4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kp79mfbbx"/><path class="wkurt-npl"/><path class="gk6duor4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:calico-light" {...props}></Icon>
