<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uucv2_foa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uucv2_foa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:badge" {...props}></Icon>
