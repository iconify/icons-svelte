<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5lb52u8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r5lb52u8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:eye-add" {...props}></Icon>
