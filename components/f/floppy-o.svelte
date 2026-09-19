<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc8wj-c_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="jc8wj-c_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:floppy-o" {...props}></Icon>
