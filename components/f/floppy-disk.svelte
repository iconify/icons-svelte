<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pboeh-bjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="pboeh-bjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:floppy-disk" {...props}></Icon>
