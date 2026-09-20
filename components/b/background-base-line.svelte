<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oah2h5byt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oah2h5byt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:background-base-line" {...props}></Icon>
