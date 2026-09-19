<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zin2cpjap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":961,"height":960};
const content = `<path class="zin2cpjap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:dominoone" {...props}></Icon>
