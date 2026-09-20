<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr_1l7bfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kr_1l7bfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:fire-extinguisher" {...props}></Icon>
