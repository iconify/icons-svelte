<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkwl28-lb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dkwl28-lb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:light-sabers" {...props}></Icon>
