<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l101v0bgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l101v0bgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:friends-of-hue-eikon" {...props}></Icon>
