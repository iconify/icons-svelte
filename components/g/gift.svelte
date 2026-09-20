<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2q0fmb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y2q0fmb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:gift" {...props}></Icon>
