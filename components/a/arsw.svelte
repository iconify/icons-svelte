<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjiisjjws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bjiisjjws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:arsw" {...props}></Icon>
