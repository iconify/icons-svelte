<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngex8nbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ngex8nbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:frame" {...props}></Icon>
