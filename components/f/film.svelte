<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnef2_4zn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnef2_4zn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:film" {...props}></Icon>
