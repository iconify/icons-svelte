<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uezj0bb4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uezj0bb4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:life-jacket" {...props}></Icon>
