<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzze5jbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rzze5jbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:chili-pepper" {...props}></Icon>
