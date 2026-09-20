<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-56_ib6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y-56_ib6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:download-alt" {...props}></Icon>
