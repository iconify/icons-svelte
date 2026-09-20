<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1d_0zbbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1d_0zbbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:globe-solid" {...props}></Icon>
