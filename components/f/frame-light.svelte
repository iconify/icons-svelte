<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucmw7d4mr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ucmw7d4mr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:frame-light" {...props}></Icon>
