<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7ajkhrwp.css';
import '../../css/z/zb6pr8b2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y7ajkhrwp"/><path class="zb6pr8b2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloud-sun-bold" {...props}></Icon>
