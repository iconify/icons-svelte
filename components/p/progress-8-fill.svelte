<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_7g23j3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_7g23j3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:progress-8-fill" {...props}></Icon>
