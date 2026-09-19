<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg25gqbsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eg25gqbsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:property-relationship" {...props}></Icon>
