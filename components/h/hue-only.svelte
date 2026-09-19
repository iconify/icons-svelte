<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-dvttbuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-dvttbuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:hue-only" {...props}></Icon>
