<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkgqa_yut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wkgqa_yut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-wind-20-bold" {...props}></Icon>
