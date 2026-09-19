<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km241ybxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="km241ybxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lightning-mask" {...props}></Icon>
