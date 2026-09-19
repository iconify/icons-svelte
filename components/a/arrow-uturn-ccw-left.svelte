<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2x2j3ulr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="j2x2j3ulr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrow-uturn-ccw-left" {...props}></Icon>
