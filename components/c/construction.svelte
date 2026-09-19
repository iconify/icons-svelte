<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_cr_6bcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v_cr_6bcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:construction" {...props}></Icon>
