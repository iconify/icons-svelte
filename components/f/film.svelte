<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvt6tyb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="rvt6tyb5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:film" {...props}></Icon>
