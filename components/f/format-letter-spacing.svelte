<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjpy1hcup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pjpy1hcup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-letter-spacing" {...props}></Icon>
