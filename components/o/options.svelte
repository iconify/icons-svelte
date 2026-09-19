<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epnbenbmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="epnbenbmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:options" {...props}></Icon>
