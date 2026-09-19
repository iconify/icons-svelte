<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdr_rfb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mdr_rfb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:checked-shield" {...props}></Icon>
