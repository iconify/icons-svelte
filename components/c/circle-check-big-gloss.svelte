<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7fm4wb9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7fm4wb9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-check-big-gloss" {...props}></Icon>
