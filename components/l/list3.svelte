<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw69zccsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vw69zccsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:list3" {...props}></Icon>
