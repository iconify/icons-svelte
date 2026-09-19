<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbs9eebdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wbs9eebdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pen-fountain" {...props}></Icon>
