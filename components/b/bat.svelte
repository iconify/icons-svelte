<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d479d2bzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d479d2bzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bat" {...props}></Icon>
