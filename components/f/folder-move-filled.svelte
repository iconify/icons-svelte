<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tn__gvaae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tn__gvaae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:folder-move-filled" {...props}></Icon>
