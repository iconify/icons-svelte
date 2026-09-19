<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tppfsxdkc.css';
import '../../css/d/dosysb90i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tppfsxdkc"/><path class="dosysb90i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:logo-vue" {...props}></Icon>
