<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg32kgb4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tg32kgb4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:james-bond-aperture" {...props}></Icon>
