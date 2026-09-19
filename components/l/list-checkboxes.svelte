<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dijn8n6ng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dijn8n6ng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:list-checkboxes" {...props}></Icon>
