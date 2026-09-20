<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvdsl_bar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zvdsl_bar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hand-paper-solid" {...props}></Icon>
