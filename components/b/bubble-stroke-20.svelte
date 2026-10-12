<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khwlhgbim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="khwlhgbim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bubble-stroke-20" {...props}></Icon>
