<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsurmjdjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hsurmjdjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:alarm-clock-plus" {...props}></Icon>
