<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt8-sfmif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dt8-sfmif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:files" {...props}></Icon>
