<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms0ln98en.css';
import '../../css/i/i3opoge7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ms0ln98en"/><path class="i3opoge7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:quire-ink-light" {...props}></Icon>
