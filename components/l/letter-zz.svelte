<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncsfrccoq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ncsfrccoq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:letter-zz" {...props}></Icon>
