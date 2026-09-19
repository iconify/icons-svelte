<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9gygm7nx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9gygm7nx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-message-alt" {...props}></Icon>
