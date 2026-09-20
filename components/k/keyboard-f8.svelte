<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z27h5bbzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z27h5bbzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:keyboard-f8" {...props}></Icon>
