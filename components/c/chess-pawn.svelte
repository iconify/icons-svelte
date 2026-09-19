<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mik1ovm0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="mik1ovm0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:chess-pawn" {...props}></Icon>
