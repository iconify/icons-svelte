<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjvrhdl8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="sjvrhdl8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:bars-arrow-up" {...props}></Icon>
