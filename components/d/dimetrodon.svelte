<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni2wf1t7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ni2wf1t7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dimetrodon" {...props}></Icon>
