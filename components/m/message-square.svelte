<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6yrju2ef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o6yrju2ef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:message-square" {...props}></Icon>
