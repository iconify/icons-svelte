<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al-vmtb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="al-vmtb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:captions-off" {...props}></Icon>
