<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn-l5uixg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qn-l5uixg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heading-5-line" {...props}></Icon>
