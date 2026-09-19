<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndtze0b0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ndtze0b0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:misdirection" {...props}></Icon>
