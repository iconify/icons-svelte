<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfsp98bra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sfsp98bra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:histogram" {...props}></Icon>
