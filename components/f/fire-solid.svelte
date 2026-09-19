<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn0gp5bmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qn0gp5bmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:fire-solid" {...props}></Icon>
