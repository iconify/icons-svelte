<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tolubvlml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tolubvlml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:generic-device-software-alarm" {...props}></Icon>
