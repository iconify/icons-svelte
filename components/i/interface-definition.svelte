<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axf4zelnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="axf4zelnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:interface-definition" {...props}></Icon>
