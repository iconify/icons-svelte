<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1_0f7bzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a1_0f7bzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:resize-h" {...props}></Icon>
