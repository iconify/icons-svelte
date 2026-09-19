<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe9si9r_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oe9si9r_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:coiling-curl" {...props}></Icon>
