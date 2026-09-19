<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lly1zw81b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="lly1zw81b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:camera-filters" {...props}></Icon>
