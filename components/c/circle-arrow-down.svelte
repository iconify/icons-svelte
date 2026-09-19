<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbku26h_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tbku26h_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-arrow-down" {...props}></Icon>
