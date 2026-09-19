<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zn9agurgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zn9agurgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:banjo" {...props}></Icon>
