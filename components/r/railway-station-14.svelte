<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd0hb1b-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="pd0hb1b-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:railway-station-14" {...props}></Icon>
