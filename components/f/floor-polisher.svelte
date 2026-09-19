<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsi4k-bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hsi4k-bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:floor-polisher" {...props}></Icon>
