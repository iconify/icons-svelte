<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qitgpr0fk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qitgpr0fk wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bike-gloss" {...props}></Icon>
