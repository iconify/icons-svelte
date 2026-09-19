<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u17lwpywi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u17lwpywi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-bot" {...props}></Icon>
