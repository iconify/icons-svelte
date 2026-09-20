<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm_1i27sj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vm_1i27sj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:quicktime" {...props}></Icon>
