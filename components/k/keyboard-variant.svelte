<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x27z5vb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x27z5vb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:keyboard-variant" {...props}></Icon>
