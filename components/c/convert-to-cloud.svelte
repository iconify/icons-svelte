<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whpbu3b6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="whpbu3b6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:convert-to-cloud" {...props}></Icon>
