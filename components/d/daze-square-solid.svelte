<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc26d0b8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tc26d0b8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:daze-square-solid" {...props}></Icon>
