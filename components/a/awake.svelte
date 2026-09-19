<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6b6ghbzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k6b6ghbzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:awake" {...props}></Icon>
