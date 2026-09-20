<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0-z5uslb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z0-z5uslb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:pathfinder-square-minus-front-1-remix" {...props}></Icon>
