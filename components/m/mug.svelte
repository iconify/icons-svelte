<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_3n6mb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":896};
const content = `<path class="j_3n6mb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:mug" {...props}></Icon>
