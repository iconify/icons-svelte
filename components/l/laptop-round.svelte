<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9iqmdbrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g9iqmdbrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:laptop-round" {...props}></Icon>
