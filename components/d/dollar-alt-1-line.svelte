<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl52pmbxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tl52pmbxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:dollar-alt-1-line" {...props}></Icon>
