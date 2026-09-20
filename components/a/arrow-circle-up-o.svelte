<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcy-b-u_j.css';
import '../../css/u/u-e1w8b5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xcy-b-u_j"/><path class="u-e1w8b5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:arrow-circle-up-o" {...props}></Icon>
