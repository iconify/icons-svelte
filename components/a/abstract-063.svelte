<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp3xwkydj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wp3xwkydj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-063" {...props}></Icon>
