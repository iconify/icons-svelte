<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do3v0r02q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="do3v0r02q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:globe-alt" {...props}></Icon>
