<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fowx1obfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fowx1obfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lightning-shadow" {...props}></Icon>
