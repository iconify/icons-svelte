<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw8qjxovw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lw8qjxovw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:robot-vacuum-play" {...props}></Icon>
