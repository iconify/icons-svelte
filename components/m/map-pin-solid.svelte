<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhxc8acwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rhxc8acwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:map-pin-solid" {...props}></Icon>
