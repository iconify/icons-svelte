<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qets41bxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qets41bxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:copy-check-solid" {...props}></Icon>
