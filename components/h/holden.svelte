<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsee1xklu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jsee1xklu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:holden" {...props}></Icon>
