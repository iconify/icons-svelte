<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7c05bzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="sv7c05bzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:chevron-down-fill-12" {...props}></Icon>
