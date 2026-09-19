<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hofvibb9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hofvibb9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:encryption" {...props}></Icon>
