<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hng5s4j4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="hng5s4j4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:dashboard" {...props}></Icon>
