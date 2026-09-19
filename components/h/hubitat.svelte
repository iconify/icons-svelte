<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw9c-cb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qw9c-cb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:hubitat" {...props}></Icon>
