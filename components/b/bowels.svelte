<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx6fccchl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sx6fccchl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bowels" {...props}></Icon>
