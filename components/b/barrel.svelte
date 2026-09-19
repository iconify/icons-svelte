<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6qv5xbnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":512};
const content = `<path class="b6qv5xbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:barrel" {...props}></Icon>
