<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z29ng0f6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z29ng0f6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:layout-2-line" {...props}></Icon>
