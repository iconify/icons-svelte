<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye3rocb0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ye3rocb0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:one-circle-solid" {...props}></Icon>
