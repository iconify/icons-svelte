<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzw-toepp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzw-toepp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:libra-line" {...props}></Icon>
