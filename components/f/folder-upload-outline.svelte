<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxbwv0bzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxbwv0bzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-upload-outline" {...props}></Icon>
