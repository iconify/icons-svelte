<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu2b7hb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nu2b7hb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:google-plus" {...props}></Icon>
