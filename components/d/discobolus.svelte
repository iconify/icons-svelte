<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voyz4-b1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="voyz4-b1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:discobolus" {...props}></Icon>
