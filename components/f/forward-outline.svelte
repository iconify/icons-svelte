<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhjd6lxmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qhjd6lxmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:forward-outline" {...props}></Icon>
