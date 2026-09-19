<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rteynoumo.css';
import '../../css/z/zzp6lsbpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rteynoumo"/><path class="zzp6lsbpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:copy-file" {...props}></Icon>
