<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz-k09b1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vz-k09b1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:plus" {...props}></Icon>
