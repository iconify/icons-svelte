<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swtptacfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="swtptacfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chevron-mini" {...props}></Icon>
