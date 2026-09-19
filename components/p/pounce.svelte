<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdzm_ubkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sdzm_ubkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pounce" {...props}></Icon>
