<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzmwirk9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kzmwirk9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:heartburn" {...props}></Icon>
