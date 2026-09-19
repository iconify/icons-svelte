<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-io-bc4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-io-bc4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:folder-output" {...props}></Icon>
