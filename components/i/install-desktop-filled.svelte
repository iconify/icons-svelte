<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5fihgbly.css';
import '../../css/n/npbkqyb3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5fihgbly"/><path class="npbkqyb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:install-desktop-filled" {...props}></Icon>
