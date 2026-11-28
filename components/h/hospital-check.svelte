<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcdsfccxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hcdsfccxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:hospital-check" {...props}></Icon>
