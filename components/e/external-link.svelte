<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmq9zib2l.css';
import '../../css/x/xv3ps-cxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wmq9zib2l"/><path class="xv3ps-cxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:external-link" {...props}></Icon>
