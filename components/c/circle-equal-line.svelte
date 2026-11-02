<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s095mkbnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s095mkbnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:circle-equal-line" {...props}></Icon>
