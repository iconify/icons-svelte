<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffh97zhvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ffh97zhvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-off-solid" {...props}></Icon>
