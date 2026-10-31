<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3rc2dbho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3rc2dbho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-close-corner-round" {...props}></Icon>
