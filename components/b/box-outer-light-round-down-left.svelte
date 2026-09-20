<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci5p-rb7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ci5p-rb7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-round-down-left" {...props}></Icon>
