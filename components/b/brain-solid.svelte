<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6ampvbvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6ampvbvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:brain-solid" {...props}></Icon>
