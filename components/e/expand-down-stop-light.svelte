<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wn4xu6bal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wn4xu6bal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:expand-down-stop-light" {...props}></Icon>
