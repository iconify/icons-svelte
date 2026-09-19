<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u56k5mb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u56k5mb2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fluffy-wing" {...props}></Icon>
