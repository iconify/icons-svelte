<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3zkh7vhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="u3zkh7vhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:axial-reflecting-dish-with-tripod-antenna" {...props}></Icon>
