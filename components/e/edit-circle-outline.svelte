<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxo87q4fu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxo87q4fu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:edit-circle-outline" {...props}></Icon>
