<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybuk2yvcd.css';
import '../../css/m/m9lolpbrw.css';
import '../../css/q/qdyu2hbul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ybuk2yvcd"/><path class="m9lolpbrw"/><path class="qdyu2hbul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-defender-light" {...props}></Icon>
