<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bck-16bdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bck-16bdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:folder-arrow-down" {...props}></Icon>
