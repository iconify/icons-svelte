<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ceb7hcupy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ceb7hcupy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:arrows-long-down" {...props}></Icon>
