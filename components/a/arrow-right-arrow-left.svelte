<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdjls4h-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mdjls4h-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrow-right-arrow-left" {...props}></Icon>
