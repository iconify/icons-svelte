<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4kmxzbqa.css';
import '../../css/m/m2awv3b3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="l4kmxzbqa"/><path class="m2awv3b3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:godot" {...props}></Icon>
