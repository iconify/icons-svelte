<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nludjwbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nludjwbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:health-capsule" {...props}></Icon>
