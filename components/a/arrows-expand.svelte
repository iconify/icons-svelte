<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3k5x5h4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r3k5x5h4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrows-expand" {...props}></Icon>
