<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aetuanbcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="aetuanbcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:clipboard-check-fill-16" {...props}></Icon>
