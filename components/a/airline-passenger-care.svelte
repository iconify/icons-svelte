<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjvnk_omj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xjvnk_omj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:airline-passenger-care" {...props}></Icon>
