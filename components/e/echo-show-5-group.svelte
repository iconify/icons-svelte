<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6v85no4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6v85no4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:echo-show-5-group" {...props}></Icon>
