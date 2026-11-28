<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk_4jabvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dk_4jabvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:lightbulb-heart" {...props}></Icon>
