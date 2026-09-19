<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skqg7ttpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="skqg7ttpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:battle-net" {...props}></Icon>
