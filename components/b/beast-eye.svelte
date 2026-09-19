<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aki4zgn5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aki4zgn5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:beast-eye" {...props}></Icon>
