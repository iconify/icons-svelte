<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pl268cndx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pl268cndx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hoodie" {...props}></Icon>
