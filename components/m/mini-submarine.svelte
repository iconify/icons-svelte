<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfav0twys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kfav0twys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mini-submarine" {...props}></Icon>
