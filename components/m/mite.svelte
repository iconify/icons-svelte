<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlmq5wygn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hlmq5wygn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mite" {...props}></Icon>
