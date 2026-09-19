<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqnfig0ya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kqnfig0ya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:kitchen-scale" {...props}></Icon>
