<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4jqe6-xz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4jqe6-xz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:plant-pot-solid" {...props}></Icon>
