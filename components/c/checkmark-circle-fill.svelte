<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyj3p-b1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="pyj3p-b1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:checkmark-circle-fill" {...props}></Icon>
