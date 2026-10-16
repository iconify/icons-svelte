<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuwqdwh-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tuwqdwh-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:order-book-20" {...props}></Icon>
