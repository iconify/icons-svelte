<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfbbxhmml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tfbbxhmml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:caret-down" {...props}></Icon>
