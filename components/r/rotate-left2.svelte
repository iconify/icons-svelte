<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n284sfe8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n284sfe8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:rotate-left2" {...props}></Icon>
