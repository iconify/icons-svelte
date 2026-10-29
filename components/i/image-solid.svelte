<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahad8xbte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahad8xbte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:image-solid" {...props}></Icon>
