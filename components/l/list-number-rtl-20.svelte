<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3vocxb4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i3vocxb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:list-number-rtl-20" {...props}></Icon>
