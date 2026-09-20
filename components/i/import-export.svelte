<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tn64yx6un.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tn64yx6un"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:import-export" {...props}></Icon>
