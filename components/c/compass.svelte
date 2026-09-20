<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek34zrbxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ek34zrbxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:compass" {...props}></Icon>
