<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isfks3eqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="isfks3eqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-5-clubs" {...props}></Icon>
