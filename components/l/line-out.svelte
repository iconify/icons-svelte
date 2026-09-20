<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz0b9lmct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yz0b9lmct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:line-out" {...props}></Icon>
