<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3v4iib0v.css';
import '../../css/m/m364hlh3h.css';
import '../../css/l/l97nb-quh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s3v4iib0v"/><path class="m364hlh3h"/><circle class="l97nb-quh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-wifi-2" {...props}></Icon>
