<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp9m-vbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xp9m-vbgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:check" {...props}></Icon>
