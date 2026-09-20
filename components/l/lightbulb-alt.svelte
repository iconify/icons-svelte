<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmaquobvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dmaquobvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:lightbulb-alt" {...props}></Icon>
