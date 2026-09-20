<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwt2_zb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wwt2_zb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:kodi-logo" {...props}></Icon>
