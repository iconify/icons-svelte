<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv6l8fblw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yv6l8fblw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:box-padding" {...props}></Icon>
