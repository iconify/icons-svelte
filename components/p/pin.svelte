<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktcsf7b2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktcsf7b2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:pin" {...props}></Icon>
