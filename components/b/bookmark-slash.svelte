<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sktsi7btg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sktsi7btg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:bookmark-slash" {...props}></Icon>
