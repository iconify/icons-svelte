<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1iia1cmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l1iia1cmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:evil-moon" {...props}></Icon>
