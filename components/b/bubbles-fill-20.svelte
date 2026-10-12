<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1p82db_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a1p82db_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bubbles-fill-20" {...props}></Icon>
