<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8pfw9bnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":112,"height":384};
const content = `<path class="w8pfw9bnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:caret-right" {...props}></Icon>
