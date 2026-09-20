<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr_nnrqul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yr_nnrqul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:play-outline" {...props}></Icon>
