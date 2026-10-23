<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf06q3b-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zf06q3b-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:globe-check" {...props}></Icon>
