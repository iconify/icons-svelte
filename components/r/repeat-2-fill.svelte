<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygdn8ccah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygdn8ccah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:repeat-2-fill" {...props}></Icon>
