<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vady1na6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vady1na6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:golf-fill-round" {...props}></Icon>
