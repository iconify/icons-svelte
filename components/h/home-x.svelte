<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1tclcbex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q1tclcbex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:home-x" {...props}></Icon>
