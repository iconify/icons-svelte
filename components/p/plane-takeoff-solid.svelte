<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8d4iybyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8d4iybyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:plane-takeoff-solid" {...props}></Icon>
