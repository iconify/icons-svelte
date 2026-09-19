<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g908y3bfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="g908y3bfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:arrow-down-on-square-stack" {...props}></Icon>
