<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrctc3yce.css';
import '../../css/o/ow7qimb4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hrctc3yce"/><path class="ow7qimb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloud-storm-bold" {...props}></Icon>
