<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3pkl-tvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h3pkl-tvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:paintbrush" {...props}></Icon>
