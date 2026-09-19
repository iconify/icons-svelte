<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwiky-9zq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mwiky-9zq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:rectangles-4" {...props}></Icon>
