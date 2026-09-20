<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufww38b4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="ufww38b4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:arrow-down" {...props}></Icon>
