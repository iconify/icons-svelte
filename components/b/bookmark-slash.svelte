<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghf9fibui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghf9fibui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bookmark-slash" {...props}></Icon>
