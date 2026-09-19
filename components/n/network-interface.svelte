<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltxah4b-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ltxah4b-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:network-interface" {...props}></Icon>
