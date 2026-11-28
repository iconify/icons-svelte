<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5g9_vn4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y5g9_vn4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:meeting-plus" {...props}></Icon>
