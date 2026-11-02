<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igc5pzbwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="igc5pzbwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clipboard-pen-line-line" {...props}></Icon>
