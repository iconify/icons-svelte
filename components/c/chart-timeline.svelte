<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccwuv1wgp.css';
import '../../css/a/anaf4rr2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ccwuv1wgp"/><path class="anaf4rr2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:chart-timeline" {...props}></Icon>
