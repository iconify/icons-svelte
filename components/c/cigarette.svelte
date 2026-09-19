<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn18foy5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hn18foy5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cigarette" {...props}></Icon>
