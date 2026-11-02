<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxlmmx9sx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxlmmx9sx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clock-7-line" {...props}></Icon>
