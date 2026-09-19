<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtjx-7-rw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wtjx-7-rw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lob-arrow" {...props}></Icon>
