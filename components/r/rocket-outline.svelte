<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9fy5tbbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v9fy5tbbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:rocket-outline" {...props}></Icon>
