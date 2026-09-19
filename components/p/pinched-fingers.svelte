<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/witxw5bwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="witxw5bwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:pinched-fingers" {...props}></Icon>
