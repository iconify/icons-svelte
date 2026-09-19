<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wffg6bc4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wffg6bc4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:fastleft" {...props}></Icon>
