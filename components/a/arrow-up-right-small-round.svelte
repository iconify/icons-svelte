<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vb7dkx9rl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vb7dkx9rl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-up-right-small-round" {...props}></Icon>
