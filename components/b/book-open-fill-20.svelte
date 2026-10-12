<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2a06bc3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g2a06bc3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:book-open-fill-20" {...props}></Icon>
