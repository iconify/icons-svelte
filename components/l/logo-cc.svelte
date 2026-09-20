<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpqjhyevn.css';
import '../../css/i/i5eb24tdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zpqjhyevn"/><path class="i5eb24tdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:logo-cc" {...props}></Icon>
