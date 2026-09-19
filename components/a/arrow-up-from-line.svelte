<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdq-tsbem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zdq-tsbem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-up-from-line" {...props}></Icon>
