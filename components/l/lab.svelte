<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5gj62mav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v5gj62mav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:lab" {...props}></Icon>
