<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxcz66biy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxcz66biy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:flow-parallel-fill" {...props}></Icon>
