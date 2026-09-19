<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_hnjcrah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l_hnjcrah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:calculation" {...props}></Icon>
