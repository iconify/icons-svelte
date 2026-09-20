<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlg3a0b6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wlg3a0b6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-word-2013-dark" {...props}></Icon>
