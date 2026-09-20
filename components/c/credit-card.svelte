<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayrxfubgw.css';
import '../../css/b/b8neo7vhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ayrxfubgw"/><path class="b8neo7vhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:credit-card" {...props}></Icon>
