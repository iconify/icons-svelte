<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw-ghd7bo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="hw-ghd7bo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:recycling-11" {...props}></Icon>
