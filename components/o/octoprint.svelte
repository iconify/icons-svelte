<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w040a9bcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w040a9bcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:octoprint" {...props}></Icon>
