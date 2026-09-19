<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kemw-9b0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kemw-9b0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:rectangle-stack-solid" {...props}></Icon>
