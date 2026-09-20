<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erora1bam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="erora1bam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:heart3" {...props}></Icon>
