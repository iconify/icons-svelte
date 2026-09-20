<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsr1kofml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsr1kofml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:i3" {...props}></Icon>
