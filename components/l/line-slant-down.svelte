<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7brm4due.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="j7brm4due"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:line-slant-down" {...props}></Icon>
