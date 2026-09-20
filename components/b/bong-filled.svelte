<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anu_as0ik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="anu_as0ik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bong-filled" {...props}></Icon>
