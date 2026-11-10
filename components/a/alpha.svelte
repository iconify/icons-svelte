<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrdrucbcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrdrucbcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:alpha" {...props}></Icon>
