<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oiy7b0mbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="oiy7b0mbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:dreamweaver" {...props}></Icon>
