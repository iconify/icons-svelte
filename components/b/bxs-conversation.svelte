<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0r_-hb1w.css';
import '../../css/u/um0weqbpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0r_-hb1w"/><path class="um0weqbpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-conversation" {...props}></Icon>
