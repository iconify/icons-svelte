<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhvfzxc8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rhvfzxc8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:h" {...props}></Icon>
