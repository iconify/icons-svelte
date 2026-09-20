<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zawatokrf.css';
import '../../css/l/lb8np0b7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zawatokrf"/><path class="lb8np0b7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:food-drink-fried-chicken" {...props}></Icon>
