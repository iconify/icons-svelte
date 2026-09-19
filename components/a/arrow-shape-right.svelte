<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1vo9-x-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e1vo9-x-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrow-shape-right" {...props}></Icon>
