<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni0oi3q4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ni0oi3q4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gryffi-light" {...props}></Icon>
