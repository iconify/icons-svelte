<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0fpadcqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="d0fpadcqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:delete" {...props}></Icon>
