<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmvr9pbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cmvr9pbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:engine-slash" {...props}></Icon>
