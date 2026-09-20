<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm9ywsb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lm9ywsb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:clipboard" {...props}></Icon>
