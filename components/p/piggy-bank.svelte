<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cry053b_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cry053b_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:piggy-bank" {...props}></Icon>
