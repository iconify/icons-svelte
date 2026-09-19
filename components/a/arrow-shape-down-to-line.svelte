<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0w57jeaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="j0w57jeaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrow-shape-down-to-line" {...props}></Icon>
