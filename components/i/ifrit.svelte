<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2q-jjb0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w2q-jjb0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ifrit" {...props}></Icon>
