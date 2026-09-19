<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwylnabgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wwylnabgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:arithmetic-mean" {...props}></Icon>
