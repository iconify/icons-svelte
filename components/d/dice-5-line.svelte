<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4smpac2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4smpac2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:dice-5-line" {...props}></Icon>
