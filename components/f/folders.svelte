<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/op7a0sdgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="op7a0sdgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:folders" {...props}></Icon>
