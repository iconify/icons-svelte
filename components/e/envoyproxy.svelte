<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd8zf1-gr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hd8zf1-gr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:envoyproxy" {...props}></Icon>
