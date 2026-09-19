<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrt2jcc7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="vrt2jcc7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:decision-solid" {...props}></Icon>
