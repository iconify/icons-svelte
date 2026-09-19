<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id4wcv-7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="id4wcv-7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fomorian" {...props}></Icon>
