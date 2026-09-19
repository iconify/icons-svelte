<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji4sfc0kr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ji4sfc0kr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:money-pound-circle-fill" {...props}></Icon>
