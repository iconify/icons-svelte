<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijf0vaczb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijf0vaczb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:ai-chip" {...props}></Icon>
