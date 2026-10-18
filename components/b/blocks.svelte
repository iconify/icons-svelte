<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv5dfbb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cv5dfbb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:blocks" {...props}></Icon>
