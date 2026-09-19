<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lau9ehbpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="lau9ehbpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-up-right-circle-fill" {...props}></Icon>
