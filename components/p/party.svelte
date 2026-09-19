<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2qpr6-4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2112,"height":1920};
const content = `<path class="l2qpr6-4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:party" {...props}></Icon>
