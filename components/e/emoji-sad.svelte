<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/paa4elqqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="paa4elqqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:emoji-sad" {...props}></Icon>
