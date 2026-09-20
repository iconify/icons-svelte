<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifbbgy5pl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ifbbgy5pl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:people" {...props}></Icon>
