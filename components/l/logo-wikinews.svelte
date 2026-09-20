<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs95uib-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rs95uib-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:logo-wikinews" {...props}></Icon>
