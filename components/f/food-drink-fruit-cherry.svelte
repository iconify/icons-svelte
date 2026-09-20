<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scrsn1bbj.css';
import '../../css/t/tsynbibhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="scrsn1bbj"/><path class="tsynbibhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:food-drink-fruit-cherry" {...props}></Icon>
