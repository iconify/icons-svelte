<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc588xphk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oc588xphk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:linuxgsm-dark" {...props}></Icon>
