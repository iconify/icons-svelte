<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_6d-1f-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":448};
const content = `<path class="g_6d-1f-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:people-team" {...props}></Icon>
