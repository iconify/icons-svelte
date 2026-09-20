<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuzsm0beb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cuzsm0beb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:bell-check-solid" {...props}></Icon>
