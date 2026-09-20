<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sizbcuz9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sizbcuz9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:flash" {...props}></Icon>
