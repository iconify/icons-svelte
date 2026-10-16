<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzc1gb6wy.css';
import '../../css/q/qvjlz2b3k.css';
import '../../css/y/yfoxxnbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dzc1gb6wy"/><path class="qvjlz2b3k"/><path class="yfoxxnbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chemical-plant-20-bold" {...props}></Icon>
