<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yps82ibbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":800,"height":800};
const content = `<path class="yps82ibbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:amplitude-icon" {...props}></Icon>
