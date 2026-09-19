<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhkv8stfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhkv8stfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:camera-person" {...props}></Icon>
