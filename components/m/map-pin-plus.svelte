<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyrp0obts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cyrp0obts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:map-pin-plus" {...props}></Icon>
