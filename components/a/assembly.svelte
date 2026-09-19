<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb789wboj.css';
import '../../css/t/t79m5jbmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bb789wboj"/><path class="t79m5jbmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:assembly" {...props}></Icon>
