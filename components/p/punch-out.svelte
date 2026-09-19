<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y93_u216t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="y93_u216t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:punch-out" {...props}></Icon>
