<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txdqesqov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="txdqesqov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:musical-notes" {...props}></Icon>
