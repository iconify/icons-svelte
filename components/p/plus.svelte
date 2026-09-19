<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt_5ujbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wt_5ujbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:plus" {...props}></Icon>
