<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zytqajcxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zytqajcxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:checked-2" {...props}></Icon>
