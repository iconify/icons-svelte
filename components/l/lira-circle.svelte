<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c07wgpbod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c07wgpbod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:lira-circle" {...props}></Icon>
