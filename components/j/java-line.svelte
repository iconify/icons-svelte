<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uezf65v5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uezf65v5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:java-line" {...props}></Icon>
