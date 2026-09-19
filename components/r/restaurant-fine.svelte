<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7r-q4bef.css';
import '../../css/k/k-aete30d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c7r-q4bef"/><path class="k-aete30d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:restaurant-fine" {...props}></Icon>
