<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkzyu1bkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hkzyu1bkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:cubes" {...props}></Icon>
