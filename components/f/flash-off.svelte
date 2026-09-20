<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-5aq062x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-5aq062x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:flash-off" {...props}></Icon>
