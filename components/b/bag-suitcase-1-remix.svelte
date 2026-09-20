<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm4gcybwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mm4gcybwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bag-suitcase-1-remix" {...props}></Icon>
