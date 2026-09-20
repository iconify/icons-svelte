<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn6ymjb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hn6ymjb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:htop" {...props}></Icon>
