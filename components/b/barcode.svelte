<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwjhm6bam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rwjhm6bam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:barcode" {...props}></Icon>
