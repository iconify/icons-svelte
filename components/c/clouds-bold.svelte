<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewaos-x_y.css';
import '../../css/p/p2vfxjbvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewaos-x_y"/><path class="p2vfxjbvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clouds-bold" {...props}></Icon>
