<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/larasbaqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="larasbaqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:hourglass" {...props}></Icon>
