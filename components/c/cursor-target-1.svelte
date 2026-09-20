<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tys5xt2qf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tys5xt2qf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:cursor-target-1" {...props}></Icon>
