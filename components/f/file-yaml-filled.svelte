<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bul2c6-4f.css';
import '../../css/a/adspdac1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bul2c6-4f"/><path class="adspdac1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-yaml-filled" {...props}></Icon>
