<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw9m3wb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yw9m3wb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:arrow-down" {...props}></Icon>
