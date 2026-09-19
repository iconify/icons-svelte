<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvww-2n-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nvww-2n-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:chess-pawn" {...props}></Icon>
