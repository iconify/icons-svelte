<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsh9tzb6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tsh9tzb6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:metronome" {...props}></Icon>
