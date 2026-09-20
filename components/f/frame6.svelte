<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipvtvf6ly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ipvtvf6ly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:frame6" {...props}></Icon>
