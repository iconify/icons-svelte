<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/va83vo2ru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="va83vo2ru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:keyboard" {...props}></Icon>
