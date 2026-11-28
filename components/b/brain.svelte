<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yznny6i3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yznny6i3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:brain" {...props}></Icon>
