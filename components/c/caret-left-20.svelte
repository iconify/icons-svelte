<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9pf6sb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h9pf6sb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:caret-left-20" {...props}></Icon>
