<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w252twlik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w252twlik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-dizzy" {...props}></Icon>
