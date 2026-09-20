<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1st9zdlh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1st9zdlh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:fast-forward" {...props}></Icon>
