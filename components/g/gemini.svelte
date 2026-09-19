<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g41_7n8pp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g41_7n8pp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:gemini" {...props}></Icon>
