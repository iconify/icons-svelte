<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cse2x4o0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cse2x4o0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:archive-alert" {...props}></Icon>
