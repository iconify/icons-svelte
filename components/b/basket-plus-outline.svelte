<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehy3bccpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ehy3bccpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:basket-plus-outline" {...props}></Icon>
