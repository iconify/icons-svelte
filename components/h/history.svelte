<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycg1fvbjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ycg1fvbjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:history" {...props}></Icon>
