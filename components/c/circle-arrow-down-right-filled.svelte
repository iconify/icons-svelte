<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/buk670bam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="buk670bam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-arrow-down-right-filled" {...props}></Icon>
