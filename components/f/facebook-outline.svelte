<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6-vuobfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y6-vuobfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:facebook-outline" {...props}></Icon>
