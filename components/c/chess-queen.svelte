<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay8f92b_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ay8f92b_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:chess-queen" {...props}></Icon>
