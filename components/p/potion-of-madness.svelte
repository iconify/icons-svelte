<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz2k0mbpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sz2k0mbpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:potion-of-madness" {...props}></Icon>
