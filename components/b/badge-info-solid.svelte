<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvcj4j3lb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pvcj4j3lb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:badge-info-solid" {...props}></Icon>
