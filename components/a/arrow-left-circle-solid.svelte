<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_uoiabps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_uoiabps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-left-circle-solid" {...props}></Icon>
