<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvvzgibti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":481,"height":754};
const content = `<path class="jvvzgibti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:2" {...props}></Icon>
