<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo4v4hbni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="oo4v4hbni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:arrow-up-on-square-stack" {...props}></Icon>
