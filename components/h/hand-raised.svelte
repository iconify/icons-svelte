<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij9xh8x8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ij9xh8x8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:hand-raised" {...props}></Icon>
