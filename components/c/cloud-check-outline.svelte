<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgclbdcyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zgclbdcyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloud-check-outline" {...props}></Icon>
