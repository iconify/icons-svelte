<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-te0_bsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o-te0_bsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bookmark-fill-20" {...props}></Icon>
