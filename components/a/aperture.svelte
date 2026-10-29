<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk23kfb_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jk23kfb_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:aperture" {...props}></Icon>
