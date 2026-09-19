<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/barxp169s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="barxp169s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:japan" {...props}></Icon>
