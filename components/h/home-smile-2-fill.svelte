<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr1x9ib_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nr1x9ib_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:home-smile-2-fill" {...props}></Icon>
