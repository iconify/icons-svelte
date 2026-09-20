<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oifwthb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oifwthb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:menu-left" {...props}></Icon>
