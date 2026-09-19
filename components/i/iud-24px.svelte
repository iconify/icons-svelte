<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8cxmrmln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y8cxmrmln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:iud-24px" {...props}></Icon>
