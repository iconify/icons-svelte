<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zguwfcbzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":472};
const content = `<path class="zguwfcbzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:code" {...props}></Icon>
