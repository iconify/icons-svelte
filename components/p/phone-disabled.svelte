<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvi8pxblc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qvi8pxblc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:phone-disabled" {...props}></Icon>
