<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhfck23re.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nhfck23re"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bayonet" {...props}></Icon>
