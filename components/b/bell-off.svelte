<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7ekynb6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o7ekynb6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:bell-off" {...props}></Icon>
