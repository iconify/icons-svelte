<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbrtgmd9d.css';
import '../../css/i/iuvb3zcak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kbrtgmd9d"/><path class="iuvb3zcak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:mobile-request" {...props}></Icon>
