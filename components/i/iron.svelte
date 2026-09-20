<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iviqw48jf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iviqw48jf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:iron" {...props}></Icon>
