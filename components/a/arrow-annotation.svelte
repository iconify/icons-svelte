<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd0oqeb7g.css';
import '../../css/u/uvsy0xydv.css';
import '../../css/u/uq2nvxbgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bd0oqeb7g"/><path class="uvsy0xydv"/><path class="uq2nvxbgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:arrow-annotation" {...props}></Icon>
