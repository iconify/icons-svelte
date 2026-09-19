<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxth2iboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cxth2iboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-relationship" {...props}></Icon>
