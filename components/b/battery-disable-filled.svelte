<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo3ec4yex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eo3ec4yex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:battery-disable-filled" {...props}></Icon>
