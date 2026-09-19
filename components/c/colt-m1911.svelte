<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9zy-db8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q9zy-db8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:colt-m1911" {...props}></Icon>
