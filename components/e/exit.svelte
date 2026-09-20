<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlyhh3nbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rlyhh3nbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:exit" {...props}></Icon>
