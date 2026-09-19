<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp2--e48l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xp2--e48l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:phone-paused" {...props}></Icon>
