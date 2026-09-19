<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eteeavbsa.css';
import '../../css/i/izeh2ywyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eteeavbsa"/><path class="izeh2ywyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:category-add" {...props}></Icon>
