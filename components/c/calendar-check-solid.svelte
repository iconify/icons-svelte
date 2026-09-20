<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euzmmobsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="euzmmobsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:calendar-check-solid" {...props}></Icon>
