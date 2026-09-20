<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arxe123jq.css';
import '../../css/t/tjw051bld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="arxe123jq"/><path clip-rule="evenodd" class="tjw051bld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:cloud-check-circle" {...props}></Icon>
