<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6zmjje5d.css';
import '../../css/y/yr811vbtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u6zmjje5d"/><path class="yr811vbtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:keyboard" {...props}></Icon>
