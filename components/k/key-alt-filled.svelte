<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s10zi1bam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s10zi1bam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:key-alt-filled" {...props}></Icon>
