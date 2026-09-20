<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk16tac8i.css';
import '../../css/h/hnr6sxbeb.css';
import '../../css/i/i9ou5abuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vk16tac8i"/><path class="hnr6sxbeb"/><path class="i9ou5abuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:onlyoffice-dark" {...props}></Icon>
