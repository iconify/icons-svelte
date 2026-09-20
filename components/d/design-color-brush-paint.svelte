<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7rxfh69l.css';
import '../../css/f/f1o3zmzsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n7rxfh69l"/><path class="f1o3zmzsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:design-color-brush-paint" {...props}></Icon>
