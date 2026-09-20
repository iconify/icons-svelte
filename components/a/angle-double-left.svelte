<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0b4cdb4f.css';
import '../../css/t/towwv1e5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m0b4cdb4f"/><path class="towwv1e5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:angle-double-left" {...props}></Icon>
