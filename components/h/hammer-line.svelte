<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hy_zkpb2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hy_zkpb2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:hammer-line" {...props}></Icon>
