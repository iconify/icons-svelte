<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6_haebsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="x6_haebsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:float-right-outline" {...props}></Icon>
