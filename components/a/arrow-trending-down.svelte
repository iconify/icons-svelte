<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3vi3_h6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="f3vi3_h6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:arrow-trending-down" {...props}></Icon>
