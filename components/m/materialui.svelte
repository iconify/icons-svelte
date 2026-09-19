<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0kz23gan.css';
import '../../css/b/b56fliz5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="k0kz23gan"/><path class="b56fliz5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:materialui" {...props}></Icon>
