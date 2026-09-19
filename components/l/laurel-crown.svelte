<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcck-rbdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kcck-rbdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:laurel-crown" {...props}></Icon>
