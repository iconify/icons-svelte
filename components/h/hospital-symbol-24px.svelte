<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctd5_sb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ctd5_sb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:hospital-symbol-24px" {...props}></Icon>
