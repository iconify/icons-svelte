<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdntsb80a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gdntsb80a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:evil-fork" {...props}></Icon>
