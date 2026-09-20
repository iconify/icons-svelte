<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn61-t-nk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bn61-t-nk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pocket" {...props}></Icon>
