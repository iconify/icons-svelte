<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h57cxjb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="h57cxjb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:parrot-on-zoo-uppercase" {...props}></Icon>
