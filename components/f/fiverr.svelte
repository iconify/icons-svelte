<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnttlzb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnttlzb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:fiverr" {...props}></Icon>
