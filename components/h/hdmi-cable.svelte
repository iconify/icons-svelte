<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z278zvbpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z278zvbpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:hdmi-cable" {...props}></Icon>
