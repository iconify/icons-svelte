<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clb7lobia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clb7lobia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:move-vertical-duotone-round" {...props}></Icon>
