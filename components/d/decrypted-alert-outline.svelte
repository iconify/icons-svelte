<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trvuyet0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="trvuyet0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:decrypted-alert-outline" {...props}></Icon>
