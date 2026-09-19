<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_hqabcco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z_hqabcco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cowboy-boot" {...props}></Icon>
