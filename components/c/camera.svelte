<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuzzmybhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-4};
const content = `<path class="iuzzmybhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:camera" {...props}></Icon>
