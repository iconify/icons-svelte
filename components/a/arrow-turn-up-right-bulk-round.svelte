<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kw4nc3bke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kw4nc3bke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-turn-up-right-bulk-round" {...props}></Icon>
