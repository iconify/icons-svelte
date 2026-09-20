<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8yt0_gac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q8yt0_gac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:in-ear-headphones-outline" {...props}></Icon>
