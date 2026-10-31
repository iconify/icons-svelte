<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvm_ht4ir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvm_ht4ir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-check-fill-round" {...props}></Icon>
