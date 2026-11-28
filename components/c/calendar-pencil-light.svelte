<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5z8zbx-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="v5z8zbx-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:calendar-pencil-light" {...props}></Icon>
