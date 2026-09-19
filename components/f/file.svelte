<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij1t_tb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ij1t_tb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:file" {...props}></Icon>
