<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfxt1osmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="vfxt1osmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:line-height" {...props}></Icon>
