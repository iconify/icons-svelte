<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sj807wb-b.css';
import '../../css/t/t8ed8cb_k.css';
import '../../css/u/uw_-t08lz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="sj807wb-b"/><circle class="t8ed8cb_k"/><path class="uw_-t08lz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:bee-bat" {...props}></Icon>
