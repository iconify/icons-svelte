<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0ff17z2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0ff17z2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:forbid-filled" {...props}></Icon>
