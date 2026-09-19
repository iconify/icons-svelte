<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jizav9dcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="jizav9dcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:calcdivide" {...props}></Icon>
