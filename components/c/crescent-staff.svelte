<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pag-9sbbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pag-9sbbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:crescent-staff" {...props}></Icon>
