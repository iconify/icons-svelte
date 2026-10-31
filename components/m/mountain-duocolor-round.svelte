<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3945es9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w3945es9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mountain-duocolor-round" {...props}></Icon>
