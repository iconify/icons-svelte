<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2md7htxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2md7htxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:explore-off" {...props}></Icon>
