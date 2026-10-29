<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgehlxb8p.css';
import '../../css/b/bdn4j9fmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgehlxb8p"/><path class="bdn4j9fmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:chevron-down" {...props}></Icon>
