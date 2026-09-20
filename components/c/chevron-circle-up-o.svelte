<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5o--747c.css';
import '../../css/x/xcy-b-u_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l5o--747c"/><path class="xcy-b-u_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:chevron-circle-up-o" {...props}></Icon>
