<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9l8db71u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9l8db71u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:circle-alert" {...props}></Icon>
