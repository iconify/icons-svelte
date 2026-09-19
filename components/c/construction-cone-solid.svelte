<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu5jp-b7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qu5jp-b7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:construction-cone-solid" {...props}></Icon>
