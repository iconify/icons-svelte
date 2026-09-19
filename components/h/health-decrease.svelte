<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_r6w1gbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f_r6w1gbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:health-decrease" {...props}></Icon>
