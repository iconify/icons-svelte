<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp-7kqbhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fp-7kqbhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:analytics" {...props}></Icon>
