<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i11tn-zvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i11tn-zvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pentagram-rose" {...props}></Icon>
