<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no2r2fjzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="no2r2fjzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:maggot" {...props}></Icon>
