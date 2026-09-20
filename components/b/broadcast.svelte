<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6kqbx0kr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="u6kqbx0kr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:broadcast" {...props}></Icon>
