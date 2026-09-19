<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v17n67bix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v17n67bix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:format-audio" {...props}></Icon>
