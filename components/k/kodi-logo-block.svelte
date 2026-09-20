<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj3uoc7wm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mj3uoc7wm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:kodi-logo-block" {...props}></Icon>
