<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlb2lfbch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tlb2lfbch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:robot-arm" {...props}></Icon>
