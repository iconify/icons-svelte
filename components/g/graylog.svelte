<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7dcb4o8w.css';
import '../../css/x/x6gvil5vf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k7dcb4o8w"/><path class="x6gvil5vf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:graylog" {...props}></Icon>
