<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj5xjtwfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qj5xjtwfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:lightbulb-off" {...props}></Icon>
