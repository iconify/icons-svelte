<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvk2tb3ud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvk2tb3ud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:microphone-1-filled" {...props}></Icon>
