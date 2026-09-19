<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8lp-bu2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m8lp-bu2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:brandy-bottle" {...props}></Icon>
