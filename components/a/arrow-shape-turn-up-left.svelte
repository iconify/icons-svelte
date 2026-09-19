<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8ithnbcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r8ithnbcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrow-shape-turn-up-left" {...props}></Icon>
