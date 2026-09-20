<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fld5_9bzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fld5_9bzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cloud-fog-solid" {...props}></Icon>
