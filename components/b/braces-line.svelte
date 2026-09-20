<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmf_6jbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vmf_6jbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:braces-line" {...props}></Icon>
