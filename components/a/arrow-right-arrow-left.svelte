<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4ohkvbho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="q4ohkvbho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-right-arrow-left" {...props}></Icon>
