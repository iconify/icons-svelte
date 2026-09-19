<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oul4phlqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oul4phlqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:honeypot" {...props}></Icon>
