<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/advu9ov5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="advu9ov5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ip-outline" {...props}></Icon>
