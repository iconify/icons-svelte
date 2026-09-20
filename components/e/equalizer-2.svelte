<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwho4kv5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gwho4kv5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:equalizer-2" {...props}></Icon>
