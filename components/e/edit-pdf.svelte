<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypkmywbor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ypkmywbor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:edit-pdf" {...props}></Icon>
