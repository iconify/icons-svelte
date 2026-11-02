<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5ggvfbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="w5ggvfbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:hourglass-16-solid" {...props}></Icon>
