<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hy9u_gbwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hy9u_gbwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrows-rotate-right" {...props}></Icon>
