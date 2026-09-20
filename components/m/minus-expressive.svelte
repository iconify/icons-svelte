<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rul21fapv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rul21fapv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:minus-expressive" {...props}></Icon>
