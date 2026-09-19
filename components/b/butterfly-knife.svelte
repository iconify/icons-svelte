<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/extb2-b3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="extb2-b3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:butterfly-knife" {...props}></Icon>
