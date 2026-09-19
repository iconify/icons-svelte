<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5sjv_b5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="t5sjv_b5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:double-down-arrow" {...props}></Icon>
