<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/roucozblu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="roucozblu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:panel-right-open-solid" {...props}></Icon>
