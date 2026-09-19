<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4xyx_bsy.css';
import '../../css/t/tkzh8yb2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p4xyx_bsy"/><path class="tkzh8yb2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-cloudy" {...props}></Icon>
