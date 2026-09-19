<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pptdugbsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pptdugbsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:ai" {...props}></Icon>
