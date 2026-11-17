<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk90i78jm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kk90i78jm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:homey" {...props}></Icon>
