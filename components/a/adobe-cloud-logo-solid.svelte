<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owpurc0sw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="owpurc0sw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:adobe-cloud-logo-solid" {...props}></Icon>
