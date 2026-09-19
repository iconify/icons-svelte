<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h93g3zbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="h93g3zbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:notes-fill-12" {...props}></Icon>
