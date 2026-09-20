<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bekoxbt4z.css';
import '../../css/v/vx50m9b9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="bekoxbt4z"/><path class="vx50m9b9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:image" {...props}></Icon>
