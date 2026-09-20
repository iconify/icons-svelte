<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3d_hde9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t3d_hde9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:crown3-filled" {...props}></Icon>
