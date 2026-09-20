<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe1x-fbkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qe1x-fbkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:bill" {...props}></Icon>
