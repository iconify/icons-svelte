<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7rw1rb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":700,"height":740};
const content = `<path class="j7rw1rb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:mobage" {...props}></Icon>
