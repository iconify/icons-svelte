<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7u7246jg.css';
import '../../css/k/kmzp8bb_p.css';
import '../../css/z/zzw3usbfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c7u7246jg"/><circle class="kmzp8bb_p"/><path class="zzw3usbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:data-scientist" {...props}></Icon>
