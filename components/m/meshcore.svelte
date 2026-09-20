<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xni24ebau.css';
import '../../css/e/emg8bu5vo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xni24ebau"/><path class="emg8bu5vo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:meshcore" {...props}></Icon>
