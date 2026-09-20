<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5fofrbqh.css';
import '../../css/v/vtw3o7h4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="h5fofrbqh"/><path class="vtw3o7h4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:logout" {...props}></Icon>
