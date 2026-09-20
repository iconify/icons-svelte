<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y09x49bgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y09x49bgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:docker-light" {...props}></Icon>
