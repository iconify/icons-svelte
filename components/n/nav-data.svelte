<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejgfz-b4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ejgfz-b4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:nav-data" {...props}></Icon>
