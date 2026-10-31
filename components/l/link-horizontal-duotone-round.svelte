<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2lv_5byc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n2lv_5byc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:link-horizontal-duotone-round" {...props}></Icon>
