<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2smo5btm.css';
import '../../css/k/k52gxob7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h2smo5btm"/><path class="k52gxob7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:design-stamp" {...props}></Icon>
