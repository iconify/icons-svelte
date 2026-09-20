<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne5oprr-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ne5oprr-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-horizontal-align-left" {...props}></Icon>
