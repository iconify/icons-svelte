<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glsddubls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="glsddubls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:rewind" {...props}></Icon>
