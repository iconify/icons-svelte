<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud_o9x3-n.css';
import '../../css/w/wbdo44kuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ud_o9x3-n"/><path class="wbdo44kuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:food-drink-bread" {...props}></Icon>
