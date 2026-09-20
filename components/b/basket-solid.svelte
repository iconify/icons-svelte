<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/reck4ybkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="reck4ybkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:basket-solid" {...props}></Icon>
