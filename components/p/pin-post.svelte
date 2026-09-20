<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxfn-h1ce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qxfn-h1ce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:pin-post" {...props}></Icon>
