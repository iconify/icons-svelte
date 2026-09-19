<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuij3-bjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iuij3-bjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:roots" {...props}></Icon>
