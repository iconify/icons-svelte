<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0kyk5qrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0kyk5qrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:arrow-align-h" {...props}></Icon>
