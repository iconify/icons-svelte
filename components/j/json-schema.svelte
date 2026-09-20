<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_neeqb3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":220};
const content = `<path class="e_neeqb3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:json-schema" {...props}></Icon>
