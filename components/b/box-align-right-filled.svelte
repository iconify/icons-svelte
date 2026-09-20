<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbnp4i9in.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbnp4i9in"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:box-align-right-filled" {...props}></Icon>
