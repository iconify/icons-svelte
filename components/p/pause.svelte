<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glfie7b8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="glfie7b8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:pause" {...props}></Icon>
