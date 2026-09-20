<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtt_77_2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="wtt_77_2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:prison-14" {...props}></Icon>
