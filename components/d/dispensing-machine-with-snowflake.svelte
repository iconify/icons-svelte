<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdxv9jpxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kdxv9jpxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dispensing-machine-with-snowflake" {...props}></Icon>
