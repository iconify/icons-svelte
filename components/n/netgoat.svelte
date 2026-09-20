<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5x5bmbqt.css';
import '../../css/a/axpn5ibac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z5x5bmbqt"/><path class="axpn5ibac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:netgoat" {...props}></Icon>
