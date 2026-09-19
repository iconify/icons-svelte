<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4agvvbwr.css';
import '../../css/v/vy6hizqps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o4agvvbwr"/><path class="vy6hizqps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:light-bulb-alt" {...props}></Icon>
