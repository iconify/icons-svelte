<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsp--cbzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-8,"top":-7};
const content = `<path class="fsp--cbzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:header" {...props}></Icon>
