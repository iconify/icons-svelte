<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0j7exohw.css';
import '../../css/z/zpv0rcqaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c0j7exohw"/><path class="zpv0rcqaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:ecology-windmill-2" {...props}></Icon>
