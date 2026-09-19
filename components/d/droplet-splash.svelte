<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnqlsqyqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bnqlsqyqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:droplet-splash" {...props}></Icon>
