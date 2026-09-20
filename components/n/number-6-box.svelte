<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yq5ur9bzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yq5ur9bzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:number-6-box" {...props}></Icon>
