<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm0jiu4yk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dm0jiu4yk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pelican-panel-dark" {...props}></Icon>
