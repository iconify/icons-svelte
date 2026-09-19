<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx5-5bc-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gx5-5bc-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:diplodocus" {...props}></Icon>
