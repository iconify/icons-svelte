<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8vby9b-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1856,"height":1664};
const content = `<path class="j8vby9b-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:exclamation-triangle" {...props}></Icon>
