<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kp79mfbbx.css';
import '../../css/l/lcqrf1bec.css';
import '../../css/s/sr4sabbve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kp79mfbbx"/><path class="lcqrf1bec"/><path class="sr4sabbve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:calico-light" {...props}></Icon>
