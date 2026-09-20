<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5xpi3wfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5xpi3wfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:large-arrow-down-line" {...props}></Icon>
