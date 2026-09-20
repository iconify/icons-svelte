<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nh554tb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nh554tb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:invisible-2" {...props}></Icon>
