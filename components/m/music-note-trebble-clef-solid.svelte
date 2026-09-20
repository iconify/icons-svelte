<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl_8k3bvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nl_8k3bvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:music-note-trebble-clef-solid" {...props}></Icon>
