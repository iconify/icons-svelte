<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0d1xbb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0d1xbb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:loudspeaker-filled" {...props}></Icon>
