<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urkf6-1ve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="urkf6-1ve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lightning-bow" {...props}></Icon>
