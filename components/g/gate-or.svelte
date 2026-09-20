<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckykibbpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ckykibbpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gate-or" {...props}></Icon>
