<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or70bzl6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="or70bzl6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:parrot-head" {...props}></Icon>
