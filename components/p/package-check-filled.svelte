<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4y1onb8u.css';
import '../../css/y/ybqrj5brm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o4y1onb8u"/><path class="ybqrj5brm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:package-check-filled" {...props}></Icon>
