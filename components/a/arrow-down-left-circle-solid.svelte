<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj-82_nyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aj-82_nyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-down-left-circle-solid" {...props}></Icon>
