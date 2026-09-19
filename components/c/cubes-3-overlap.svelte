<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj0jy4-my.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uj0jy4-my"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:cubes-3-overlap" {...props}></Icon>
