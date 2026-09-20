<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sipm7-qkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sipm7-qkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:heading-1" {...props}></Icon>
