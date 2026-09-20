<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpl6erble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hpl6erble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:pass-valid-line" {...props}></Icon>
