<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8-6i3bvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x8-6i3bvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-function-solid" {...props}></Icon>
