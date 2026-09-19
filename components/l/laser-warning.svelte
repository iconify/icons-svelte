<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scsbrkeec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="scsbrkeec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:laser-warning" {...props}></Icon>
