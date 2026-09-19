<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txyhcbcgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="txyhcbcgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:deployment-policy" {...props}></Icon>
