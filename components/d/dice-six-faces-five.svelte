<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmzko8bxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kmzko8bxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dice-six-faces-five" {...props}></Icon>
