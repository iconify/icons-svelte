<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9-8otbxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9-8otbxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-search-outline" {...props}></Icon>
