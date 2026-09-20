<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9r_w_bnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9r_w_bnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-settings-cog-outline" {...props}></Icon>
