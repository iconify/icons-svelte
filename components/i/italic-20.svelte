<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jaa05bc3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jaa05bc3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:italic-20" {...props}></Icon>
