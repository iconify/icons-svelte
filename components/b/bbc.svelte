<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkvwa7bal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":285};
const content = `<path class="kkvwa7bal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bbc" {...props}></Icon>
