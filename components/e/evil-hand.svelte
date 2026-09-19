<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu5qq_bkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iu5qq_bkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:evil-hand" {...props}></Icon>
