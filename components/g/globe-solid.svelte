<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utzvwf4ku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utzvwf4ku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:globe-solid" {...props}></Icon>
