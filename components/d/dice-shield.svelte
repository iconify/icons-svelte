<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur_4-tsif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ur_4-tsif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dice-shield" {...props}></Icon>
