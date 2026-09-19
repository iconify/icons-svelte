<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs2-cdbrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qs2-cdbrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:bars-2" {...props}></Icon>
