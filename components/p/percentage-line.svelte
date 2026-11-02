<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hr3ylkbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hr3ylkbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:percentage-line" {...props}></Icon>
