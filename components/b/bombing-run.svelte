<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq-27zd6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iq-27zd6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bombing-run" {...props}></Icon>
