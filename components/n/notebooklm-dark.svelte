<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz7386bgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iz7386bgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:notebooklm-dark" {...props}></Icon>
