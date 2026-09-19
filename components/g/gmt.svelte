<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u35j8-mcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u35j8-mcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:gmt" {...props}></Icon>
