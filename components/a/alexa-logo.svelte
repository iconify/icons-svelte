<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whr5vg88n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whr5vg88n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:alexa-logo" {...props}></Icon>
