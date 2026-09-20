<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0yx6g4it.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z0yx6g4it"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:location-check" {...props}></Icon>
