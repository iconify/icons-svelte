<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbj3n7r_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="zbj3n7r_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:banknotes" {...props}></Icon>
