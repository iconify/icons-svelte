<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1yhx_g5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z1yhx_g5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:controls-pause-bold" {...props}></Icon>
