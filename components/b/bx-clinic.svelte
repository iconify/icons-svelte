<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt9os31ki.css';
import '../../css/o/ox5bagm_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mt9os31ki"/><path class="ox5bagm_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-clinic" {...props}></Icon>
