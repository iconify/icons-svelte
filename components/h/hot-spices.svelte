<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcbv1h3kj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vcbv1h3kj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hot-spices" {...props}></Icon>
