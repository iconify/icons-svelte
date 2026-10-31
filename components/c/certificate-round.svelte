<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdy_6m8-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdy_6m8-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:certificate-round" {...props}></Icon>
