<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqcf44yln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqcf44yln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:list-collapse-duotone-round" {...props}></Icon>
