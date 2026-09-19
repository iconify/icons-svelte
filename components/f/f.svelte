<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0qy6t9rz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="q0qy6t9rz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:f" {...props}></Icon>
