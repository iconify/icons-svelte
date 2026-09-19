<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxc0abc3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uxc0abc3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:number-small-8" {...props}></Icon>
