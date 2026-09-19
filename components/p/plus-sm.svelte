<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uh3xl_ida.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="uh3xl_ida"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:plus-sm" {...props}></Icon>
