<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzux7hjuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jzux7hjuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:chart-pie" {...props}></Icon>
