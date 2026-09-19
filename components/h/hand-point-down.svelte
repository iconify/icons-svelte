<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edumjhbrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="edumjhbrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:hand-point-down" {...props}></Icon>
