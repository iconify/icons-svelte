<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfj06-b1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfj06-b1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-turn-left-down-fill-round" {...props}></Icon>
