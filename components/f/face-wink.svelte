<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cymb9cbzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cymb9cbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:face-wink" {...props}></Icon>
