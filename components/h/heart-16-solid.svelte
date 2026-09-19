<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex90klq7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ex90klq7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:heart-16-solid" {...props}></Icon>
