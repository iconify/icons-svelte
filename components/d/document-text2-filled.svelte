<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfj4zib1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vfj4zib1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:document-text2-filled" {...props}></Icon>
