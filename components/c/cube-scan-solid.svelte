<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsgvmwn9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nsgvmwn9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:cube-scan-solid" {...props}></Icon>
