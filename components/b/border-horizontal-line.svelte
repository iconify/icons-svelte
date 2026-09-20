<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5-fr6b_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q5-fr6b_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:border-horizontal-line" {...props}></Icon>
