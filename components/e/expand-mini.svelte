<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifxo9ybau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ifxo9ybau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:expand-mini" {...props}></Icon>
