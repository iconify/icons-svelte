<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3zwvqbge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u3zwvqbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:link-disconnected-bold" {...props}></Icon>
