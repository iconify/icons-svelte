<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmw9xcbrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmw9xcbrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:police-badge-fill" {...props}></Icon>
