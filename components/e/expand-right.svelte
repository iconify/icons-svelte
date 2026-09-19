<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-1cqfbrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c-1cqfbrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:expand-right" {...props}></Icon>
