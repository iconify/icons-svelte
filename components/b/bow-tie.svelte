<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5hvg5b5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g5hvg5b5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bow-tie" {...props}></Icon>
