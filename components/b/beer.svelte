<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euo93-5ut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="euo93-5ut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:beer" {...props}></Icon>
