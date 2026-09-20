<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz08ibbym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vz08ibbym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:note-text-minus-line" {...props}></Icon>
