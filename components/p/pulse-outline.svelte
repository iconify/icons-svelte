<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbycz7_ya.css';
import '../../css/h/hueeqab-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xbycz7_ya"/><circle class="hueeqab-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:pulse-outline" {...props}></Icon>
