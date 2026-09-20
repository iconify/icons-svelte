<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5rw2ua2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="w5rw2ua2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:cinema-14" {...props}></Icon>
