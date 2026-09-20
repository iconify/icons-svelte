<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acrih_vdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="acrih_vdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-leftbar-close-line" {...props}></Icon>
