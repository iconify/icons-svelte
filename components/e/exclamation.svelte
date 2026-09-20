<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffqs8ektl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ffqs8ektl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:exclamation" {...props}></Icon>
