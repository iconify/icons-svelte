<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uats1sbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="uats1sbjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:bookmark-alt" {...props}></Icon>
