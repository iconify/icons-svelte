<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cya-rzp4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cya-rzp4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:caret-sort" {...props}></Icon>
