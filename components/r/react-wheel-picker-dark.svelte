<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqadkkxff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="oqadkkxff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:react-wheel-picker-dark" {...props}></Icon>
