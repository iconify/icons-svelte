<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_bj8hwhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e_bj8hwhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dice-target" {...props}></Icon>
