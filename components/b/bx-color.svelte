<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk2uazbpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xk2uazbpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-color" {...props}></Icon>
