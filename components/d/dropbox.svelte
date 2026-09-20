<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qeeth9bbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qeeth9bbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dropbox" {...props}></Icon>
