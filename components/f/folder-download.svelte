<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m68_46y6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m68_46y6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:folder-download" {...props}></Icon>
