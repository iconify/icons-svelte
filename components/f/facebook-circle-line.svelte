<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4rsdhbno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4rsdhbno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:facebook-circle-line" {...props}></Icon>
