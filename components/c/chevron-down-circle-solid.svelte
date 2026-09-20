<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmbq64bam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmbq64bam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevron-down-circle-solid" {...props}></Icon>
