<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dontj7bcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dontj7bcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pierced-body" {...props}></Icon>
