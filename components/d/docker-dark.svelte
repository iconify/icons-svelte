<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n17o4wbov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n17o4wbov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:docker-dark" {...props}></Icon>
