<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv_f63b0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jv_f63b0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:moon-o" {...props}></Icon>
