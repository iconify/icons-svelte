<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5r0r42lp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="p5r0r42lp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:forward-bar-16-solid" {...props}></Icon>
