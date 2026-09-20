<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdl-6zbdg.css';
import '../../css/w/w6se-gehu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="vdl-6zbdg"/><path class="w6se-gehu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-radiology" {...props}></Icon>
