<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_w3bteiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_w3bteiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:dacia" {...props}></Icon>
