<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1m__bn8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="k1m__bn8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:drag-drop" {...props}></Icon>
