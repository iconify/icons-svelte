<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-lqkvb5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-lqkvb5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:low-beam-headlights-line" {...props}></Icon>
