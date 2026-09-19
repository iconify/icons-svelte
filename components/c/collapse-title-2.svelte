<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhe4of3su.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dhe4of3su"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:collapse-title-2" {...props}></Icon>
