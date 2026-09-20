<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s54glg70g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s54glg70g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:door-off" {...props}></Icon>
