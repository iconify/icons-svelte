<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e59f65b2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e59f65b2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:font" {...props}></Icon>
