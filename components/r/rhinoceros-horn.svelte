<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5vcnf70z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y5vcnf70z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:rhinoceros-horn" {...props}></Icon>
