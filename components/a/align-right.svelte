<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr1_5-ayd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gr1_5-ayd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:align-right" {...props}></Icon>
