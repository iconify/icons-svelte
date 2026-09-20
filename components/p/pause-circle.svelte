<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plztprbze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="plztprbze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:pause-circle" {...props}></Icon>
