<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgld--2ik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cgld--2ik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:pause-circle-solid" {...props}></Icon>
