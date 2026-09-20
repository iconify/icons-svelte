<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4fbbbcls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4fbbbcls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:page-previous-outline" {...props}></Icon>
