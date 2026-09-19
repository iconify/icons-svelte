<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9hg_bbum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e9hg_bbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ballerina-shoes" {...props}></Icon>
