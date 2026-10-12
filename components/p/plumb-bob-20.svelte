<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5g4gdxon.css';
import '../../css/c/c-2y_lb8w.css';
import '../../css/f/fpx2kva1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b5g4gdxon"/><path class="c-2y_lb8w"/><path class="fpx2kva1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plumb-bob-20" {...props}></Icon>
