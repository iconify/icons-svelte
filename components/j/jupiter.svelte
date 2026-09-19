<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5w9ww-gj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a5w9ww-gj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:jupiter" {...props}></Icon>
