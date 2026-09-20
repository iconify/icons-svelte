<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo5xuvb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zo5xuvb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account" {...props}></Icon>
