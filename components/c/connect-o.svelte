<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5kb4tbdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x5kb4tbdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:connect-o" {...props}></Icon>
