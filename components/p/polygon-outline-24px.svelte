<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdhb58bwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mdhb58bwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:polygon-outline-24px" {...props}></Icon>
