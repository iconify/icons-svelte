<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk4t1gb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yk4t1gb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-050" {...props}></Icon>
