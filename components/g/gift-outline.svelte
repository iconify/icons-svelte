<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9sxm0bwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="a9sxm0bwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:gift-outline" {...props}></Icon>
