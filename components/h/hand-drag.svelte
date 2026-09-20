<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s516_l97p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s516_l97p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:hand-drag" {...props}></Icon>
