<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ej3np33fg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ej3np33fg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:jeweled-chalice" {...props}></Icon>
