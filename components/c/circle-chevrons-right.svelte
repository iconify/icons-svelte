<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx336bxgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cx336bxgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-chevrons-right" {...props}></Icon>
