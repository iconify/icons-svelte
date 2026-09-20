<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6hp64p8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6hp64p8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:factory-building-1-bold" {...props}></Icon>
