<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afgl2wb3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afgl2wb3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:globe-alt-2-filled" {...props}></Icon>
