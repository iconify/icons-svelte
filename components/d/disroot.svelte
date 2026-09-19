<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5_iwcr4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z5_iwcr4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:disroot" {...props}></Icon>
