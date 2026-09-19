<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz5xefbiq.css';
import '../../css/a/am0b34b6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zz5xefbiq"/><path class="am0b34b6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:fit-to-screen" {...props}></Icon>
