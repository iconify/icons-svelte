<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb-2-3xob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kb-2-3xob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:capricorn" {...props}></Icon>
