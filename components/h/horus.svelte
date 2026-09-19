<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as_hcbb4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="as_hcbb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:horus" {...props}></Icon>
