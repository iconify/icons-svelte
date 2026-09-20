<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcej34bay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hcej34bay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:plane2-filled" {...props}></Icon>
