<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3v4iib0v.css';
import '../../css/l/l97nb-quh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s3v4iib0v"/><circle class="l97nb-quh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-wifi-1" {...props}></Icon>
