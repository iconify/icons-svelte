<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxu7n6der.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxu7n6der"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-file" {...props}></Icon>
