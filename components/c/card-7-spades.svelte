<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o53op-jvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o53op-jvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-7-spades" {...props}></Icon>
