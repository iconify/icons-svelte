<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh8i5_bfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rh8i5_bfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:fx" {...props}></Icon>
