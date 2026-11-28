<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwxig2-hp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwxig2-hp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:inbox-x" {...props}></Icon>
